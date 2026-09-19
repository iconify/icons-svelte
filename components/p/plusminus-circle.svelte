<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z46p-jbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z46p-jbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plusminus-circle" {...props}></Icon>
