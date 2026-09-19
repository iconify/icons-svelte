<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xty0e4bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xty0e4bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calls-incoming" {...props}></Icon>
