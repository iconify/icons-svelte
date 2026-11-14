<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/ko22q1b9a.css';
import '../../css/o/or9ywybpp.css';
import '../../css/h/hp_bkssfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ko22q1b9a"/><path class="or9ywybpp"/><path class="hp_bkssfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:idle-fee" {...props}></Icon>
