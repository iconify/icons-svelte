<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnflv5bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tnflv5bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:download" {...props}></Icon>
