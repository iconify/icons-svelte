<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atti1kbuc.css';
import '../../css/w/w57s-x_gs.css';
import '../../css/r/rkutulbsh.css';
import '../../css/q/qzguk0yob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="atti1kbuc"/><path clip-rule="evenodd" class="w57s-x_gs"/><path class="rkutulbsh"/><path class="qzguk0yob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:map-marker-1" {...props}></Icon>
