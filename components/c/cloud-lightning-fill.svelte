<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlmv45btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rlmv45btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-lightning-fill" {...props}></Icon>
