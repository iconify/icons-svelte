<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyz1lph9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyz1lph9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openapi-initiative" {...props}></Icon>
