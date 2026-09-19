<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohf2_-0nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ohf2_-0nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudsync" {...props}></Icon>
