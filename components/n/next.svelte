<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj3eh0r6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="nj3eh0r6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:next" {...props}></Icon>
