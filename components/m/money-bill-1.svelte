<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht82qccml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ht82qccml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-bill-1" {...props}></Icon>
