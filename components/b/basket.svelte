<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l14lsac5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":790};
const content = `<path class="l14lsac5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:basket" {...props}></Icon>
