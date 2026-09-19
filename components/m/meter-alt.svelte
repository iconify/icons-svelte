<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6zq0m34v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d6zq0m34v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:meter-alt" {...props}></Icon>
