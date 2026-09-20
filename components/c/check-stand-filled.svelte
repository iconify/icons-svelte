<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgkgn1aew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sgkgn1aew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:check-stand-filled" {...props}></Icon>
