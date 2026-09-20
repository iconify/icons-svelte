<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulco_5bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ulco_5bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:integral-distribute-filled" {...props}></Icon>
