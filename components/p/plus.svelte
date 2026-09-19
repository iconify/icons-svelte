<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quobr6bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="quobr6bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:plus" {...props}></Icon>
