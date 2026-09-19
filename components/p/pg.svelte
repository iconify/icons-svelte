<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vb14ysbvz.css';
import '../../css/m/mhwhjcbvw.css';
import '../../css/a/a8coxybhr.css';
import '../../css/w/w7qfhsb1m.css';
import '../../css/r/rncbqcckd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="vb14ysbvz"/><path clip-rule="evenodd" class="mhwhjcbvw"/><path clip-rule="evenodd" class="a8coxybhr"/><path clip-rule="evenodd" class="w7qfhsb1m"/><path clip-rule="evenodd" class="rncbqcckd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:pg" {...props}></Icon>
