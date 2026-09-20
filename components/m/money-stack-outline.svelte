<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgd3xjm7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kgd3xjm7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:money-stack-outline" {...props}></Icon>
