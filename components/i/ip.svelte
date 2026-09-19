<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oquv4muql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oquv4muql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ip" {...props}></Icon>
