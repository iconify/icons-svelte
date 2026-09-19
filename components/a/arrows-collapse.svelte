<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dje1_sblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dje1_sblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrows-collapse" {...props}></Icon>
