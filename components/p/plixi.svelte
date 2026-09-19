<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsvqpqtgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":488};
const content = `<path class="gsvqpqtgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:plixi" {...props}></Icon>
