<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhjdlkbru.css';
import '../../css/t/tf8s1bbdj.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zhjdlkbru"/><path class="tf8s1bbdj"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-plus-20" {...props}></Icon>
