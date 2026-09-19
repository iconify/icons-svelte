<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9rc3ab5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9rc3ab5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:deepin" {...props}></Icon>
