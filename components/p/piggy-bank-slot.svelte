<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw-8qhb8k.css';
import '../../css/a/a78cr7b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lw-8qhb8k"/><path class="a78cr7b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:piggy-bank-slot" {...props}></Icon>
