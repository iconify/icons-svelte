<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_rgv23dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_rgv23dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:close-sm" {...props}></Icon>
