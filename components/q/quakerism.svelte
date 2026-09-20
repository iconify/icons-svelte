<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_xzgb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ae_xzgb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:quakerism" {...props}></Icon>
