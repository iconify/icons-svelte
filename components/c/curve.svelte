<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9mxw7bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k9mxw7bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:curve" {...props}></Icon>
