<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyf_obcvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cyf_obcvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark" {...props}></Icon>
