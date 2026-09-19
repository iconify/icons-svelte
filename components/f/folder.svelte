<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6b9ptbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6b9ptbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:folder" {...props}></Icon>
