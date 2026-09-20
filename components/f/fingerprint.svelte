<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5nye4bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g5nye4bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fingerprint" {...props}></Icon>
