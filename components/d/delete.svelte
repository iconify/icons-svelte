<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqo-cjb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqo-cjb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:delete" {...props}></Icon>
