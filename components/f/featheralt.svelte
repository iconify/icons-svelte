<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml8beb-zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ml8beb-zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:featheralt" {...props}></Icon>
