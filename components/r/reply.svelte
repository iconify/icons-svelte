<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hio1l1djh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hio1l1djh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:reply" {...props}></Icon>
