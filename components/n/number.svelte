<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpeh4lb3t.css';
import '../../css/n/nyxp3bb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="fpeh4lb3t"/><path class="nyxp3bb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:number" {...props}></Icon>
