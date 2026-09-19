<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7w0g9z2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7w0g9z2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:minizinc" {...props}></Icon>
