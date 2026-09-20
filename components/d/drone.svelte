<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olxuds8oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":230,"height":230};
const content = `<path class="olxuds8oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:drone" {...props}></Icon>
