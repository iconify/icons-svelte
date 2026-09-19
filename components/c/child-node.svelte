<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnq6rt34g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qnq6rt34g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:child-node" {...props}></Icon>
