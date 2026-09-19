<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkwr88bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hkwr88bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:menu" {...props}></Icon>
