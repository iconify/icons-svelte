<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drp3_i9rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1632};
const content = `<path class="drp3_i9rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:child" {...props}></Icon>
