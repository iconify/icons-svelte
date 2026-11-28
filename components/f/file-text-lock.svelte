<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg5se_bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg5se_bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-lock" {...props}></Icon>
