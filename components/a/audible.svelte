<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_te8b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o5_te8b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:audible" {...props}></Icon>
