<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuszjqbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tuszjqbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleadd" {...props}></Icon>
