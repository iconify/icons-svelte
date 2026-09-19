<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikvx39bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ikvx39bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array-numbers" {...props}></Icon>
