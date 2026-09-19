<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2j38clag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a2j38clag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-with-circle-down" {...props}></Icon>
