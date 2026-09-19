<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysak76b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ysak76b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:car" {...props}></Icon>
