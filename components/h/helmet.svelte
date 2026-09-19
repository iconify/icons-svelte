<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gea7pzbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gea7pzbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:helmet" {...props}></Icon>
