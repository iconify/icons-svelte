<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un-a6pokw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="un-a6pokw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bookmark" {...props}></Icon>
