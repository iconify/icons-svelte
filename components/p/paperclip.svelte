<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn6651btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zn6651btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:paperclip" {...props}></Icon>
