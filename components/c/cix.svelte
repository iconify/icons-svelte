<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5nysbo_z.css';
import '../../css/n/nfn_d0zln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r5nysbo_z"/><path class="nfn_d0zln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cix" {...props}></Icon>
