<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqg3iacjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="lqg3iacjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:battery-25" {...props}></Icon>
