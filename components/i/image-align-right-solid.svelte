<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-5p2lb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-5p2lb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-align-right-solid" {...props}></Icon>
