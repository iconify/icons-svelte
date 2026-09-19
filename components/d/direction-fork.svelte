<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baai45q_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="baai45q_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-fork" {...props}></Icon>
