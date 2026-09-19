<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnfh_j-gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":620};
const content = `<path class="dnfh_j-gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:cloud" {...props}></Icon>
