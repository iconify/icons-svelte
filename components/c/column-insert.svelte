<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhdij880v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xhdij880v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:column-insert" {...props}></Icon>
