<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm5kcsbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cm5kcsbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:like" {...props}></Icon>
