<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbt7-c2ud.css';
import '../../css/s/sug610m-v.css';
import '../../css/g/gz0iumbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rbt7-c2ud"/><path class="sug610m-v"/><path class="gz0iumbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cocktail-48" {...props}></Icon>
