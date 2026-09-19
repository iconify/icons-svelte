<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haqpj0bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="haqpj0bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gitpod" {...props}></Icon>
