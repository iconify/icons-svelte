<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgg4lhbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wgg4lhbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:html" {...props}></Icon>
