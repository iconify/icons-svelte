<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_zkzbhbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a_zkzbhbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:handbag" {...props}></Icon>
