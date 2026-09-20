<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2_s99bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2_s99bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bolt-slash" {...props}></Icon>
