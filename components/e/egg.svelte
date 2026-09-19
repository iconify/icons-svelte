<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byjpmcj3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":448};
const content = `<path class="byjpmcj3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:egg" {...props}></Icon>
