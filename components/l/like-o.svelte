<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwy9vrrqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwy9vrrqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:like-o" {...props}></Icon>
