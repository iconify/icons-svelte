<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8-vdibbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o8-vdibbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pictureframe" {...props}></Icon>
