<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so7ecdiom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="so7ecdiom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:eye" {...props}></Icon>
