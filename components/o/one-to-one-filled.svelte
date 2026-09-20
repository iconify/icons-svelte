<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq8al8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oq8al8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:one-to-one-filled" {...props}></Icon>
