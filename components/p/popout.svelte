<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf-bfub-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tf-bfub-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:popout" {...props}></Icon>
