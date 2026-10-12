<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_p666_yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w_p666_yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:banknote-fill-20" {...props}></Icon>
