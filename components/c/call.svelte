<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypj23acfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ypj23acfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:call" {...props}></Icon>
