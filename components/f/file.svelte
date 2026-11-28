<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6-z5cb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-z5cb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file" {...props}></Icon>
