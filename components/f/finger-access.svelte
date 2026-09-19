<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/czd7etboj.css';
import '../../css/i/ihar8za-j.css';
import '../../css/d/dq9es6cpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czd7etboj"/><path class="ihar8za-j"/><path class="dq9es6cpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:finger-access" {...props}></Icon>
