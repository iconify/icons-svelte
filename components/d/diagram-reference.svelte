<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftv6d47py.css';
import '../../css/z/zrf-pobow.css';
import '../../css/h/h6775rmlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="zrf-pobow"/><path class="h6775rmlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:diagram-reference" {...props}></Icon>
