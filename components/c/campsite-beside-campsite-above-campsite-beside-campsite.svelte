<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn0mf_rjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kn0mf_rjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-beside-campsite-above-campsite-beside-campsite" {...props}></Icon>
