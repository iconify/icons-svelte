<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp7-0ubcz.css';
import '../../css/l/lxxy901ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wp7-0ubcz"/><circle class="lxxy901ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:eye" {...props}></Icon>
