<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0qbxbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vh0qbxbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:info-with-circle" {...props}></Icon>
