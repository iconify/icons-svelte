<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf2gz2hlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2gz2hlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:apps-bold" {...props}></Icon>
