<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7ksnmb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7ksnmb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:list-numbered-ltr" {...props}></Icon>
