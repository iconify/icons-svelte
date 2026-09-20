<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9l6b08cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9l6b08cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camcorder" {...props}></Icon>
