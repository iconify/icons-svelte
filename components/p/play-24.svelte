<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_vn3o3pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_vn3o3pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:play-24" {...props}></Icon>
