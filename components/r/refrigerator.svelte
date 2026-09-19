<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vluce1bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vluce1bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:refrigerator" {...props}></Icon>
