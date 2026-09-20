<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzveqhbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nzveqhbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-arrow-left" {...props}></Icon>
