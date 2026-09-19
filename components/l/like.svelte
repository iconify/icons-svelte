<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzwym2bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="dzwym2bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:like" {...props}></Icon>
