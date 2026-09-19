<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqc5nf5ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nqc5nf5ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:north-arrow" {...props}></Icon>
