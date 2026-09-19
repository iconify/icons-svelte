<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht6fsttpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ht6fsttpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:magnet" {...props}></Icon>
