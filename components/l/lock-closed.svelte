<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv3lvgb1x.css';
import '../../css/c/cp_z6dbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3lvgb1x"/><path class="cp_z6dbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:lock-closed" {...props}></Icon>
