<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvzhtd08i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zvzhtd08i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:duck" {...props}></Icon>
