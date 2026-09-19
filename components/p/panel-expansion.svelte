<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj6it4upb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xj6it4upb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:panel-expansion" {...props}></Icon>
