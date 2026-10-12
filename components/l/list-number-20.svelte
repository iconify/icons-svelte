<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv3ibbcem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lv3ibbcem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:list-number-20" {...props}></Icon>
