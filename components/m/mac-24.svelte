<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0v2eqqog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0v2eqqog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mac-24" {...props}></Icon>
