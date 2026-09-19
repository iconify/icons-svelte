<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbftq4bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lbftq4bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:progress-one" {...props}></Icon>
