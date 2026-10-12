<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd0c3gbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kd0c3gbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-fill-20" {...props}></Icon>
