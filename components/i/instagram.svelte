<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smmhmy9uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":850};
const content = `<path class="smmhmy9uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:instagram" {...props}></Icon>
