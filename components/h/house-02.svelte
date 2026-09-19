<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hl471tb-q.css';
import '../../css/h/hf3pd9fjs.css';
import '../../css/d/digy0rbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hl471tb-q"/><path class="hf3pd9fjs"/><path class="digy0rbjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:house-02" {...props}></Icon>
