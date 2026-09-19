<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prv40i33l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="prv40i33l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-medium" {...props}></Icon>
