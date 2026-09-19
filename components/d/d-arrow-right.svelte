<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tagpg-bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tagpg-bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:d-arrow-right" {...props}></Icon>
