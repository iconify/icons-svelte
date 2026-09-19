<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9fqg7bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k9fqg7bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bridge-circle-check" {...props}></Icon>
