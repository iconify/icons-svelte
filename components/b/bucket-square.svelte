<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/ham-wqb_z.css';
import '../../css/d/dwhsjmobk.css';
import '../../css/z/z6re8rbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ham-wqb_z"/><path class="dwhsjmobk"/><path class="z6re8rbyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bucket-square" {...props}></Icon>
