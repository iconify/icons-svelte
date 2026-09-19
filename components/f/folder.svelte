<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5am75sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oc5am75sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder" {...props}></Icon>
