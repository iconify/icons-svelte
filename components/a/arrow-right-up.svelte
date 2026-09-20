<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqc7jrgdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wqc7jrgdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-right-up" {...props}></Icon>
