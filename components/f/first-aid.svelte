<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a09o_zzmo.css';
import '../../css/c/ckct19qqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="a09o_zzmo"/><path class="ckct19qqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:first-aid" {...props}></Icon>
