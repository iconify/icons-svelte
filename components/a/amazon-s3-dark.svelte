<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5j_i5b7x.css';
import '../../css/m/m-hjm3bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j5j_i5b7x"/><path class="m-hjm3bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-s3-dark" {...props}></Icon>
