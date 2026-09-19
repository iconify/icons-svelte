<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh_u9bbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yh_u9bbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mergeshapes" {...props}></Icon>
