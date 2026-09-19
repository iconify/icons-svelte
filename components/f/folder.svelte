<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4e7s067m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a4e7s067m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:folder" {...props}></Icon>
