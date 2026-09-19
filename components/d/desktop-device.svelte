<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jox__zbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jox__zbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:desktop-device" {...props}></Icon>
