<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdoxu0bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":488};
const content = `<path class="jdoxu0bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:posterous" {...props}></Icon>
