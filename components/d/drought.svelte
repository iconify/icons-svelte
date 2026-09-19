<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-rkgx1cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h-rkgx1cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drought" {...props}></Icon>
