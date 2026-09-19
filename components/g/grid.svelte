<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks5a3nbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ks5a3nbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid" {...props}></Icon>
