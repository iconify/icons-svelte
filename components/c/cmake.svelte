<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiyi5t_0v.css';
import '../../css/u/ufh9qkbxk.css';
import '../../css/n/naagimbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiyi5t_0v"/><path class="ufh9qkbxk"/><path class="naagimbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cmake" {...props}></Icon>
