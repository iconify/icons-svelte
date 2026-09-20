<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr87_k8po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pr87_k8po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:reddit-outline" {...props}></Icon>
