<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqwsjp3fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fqwsjp3fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:neutral-face-in-circle-outline" {...props}></Icon>
