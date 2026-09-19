<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td-rczbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="td-rczbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rain-scattered" {...props}></Icon>
