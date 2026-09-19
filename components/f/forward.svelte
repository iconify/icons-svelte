<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj3enubxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":472};
const content = `<path class="lj3enubxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:forward" {...props}></Icon>
