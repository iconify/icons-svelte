<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs0poacqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zs0poacqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:old-phone" {...props}></Icon>
