<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iau0sn_fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="iau0sn_fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:login" {...props}></Icon>
