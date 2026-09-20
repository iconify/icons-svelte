<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uqn0ipa3k.css';
import '../../css/m/mywbnbbvg.css';
import '../../css/g/g3f2y5lcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uqn0ipa3k"/><path class="mywbnbbvg"/><path class="g3f2y5lcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-excel" {...props}></Icon>
