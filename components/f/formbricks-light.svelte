<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxqz76bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxqz76bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:formbricks-light" {...props}></Icon>
