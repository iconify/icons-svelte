<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9vfmsbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="e9vfmsbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:keyboard" {...props}></Icon>
