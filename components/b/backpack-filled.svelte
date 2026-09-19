<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h__5z1bbd.css';
import '../../css/s/s2rt5pbav.css';
import '../../css/z/zv3nb1bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h__5z1bbd"/><path class="s2rt5pbav"/><path class="zv3nb1bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backpack-filled" {...props}></Icon>
