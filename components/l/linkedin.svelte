<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io96o8bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="io96o8bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:linkedin" {...props}></Icon>
