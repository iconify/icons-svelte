<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b_mqzbbbw.css';
import '../../css/o/o0vcg8bqt.css';
import '../../css/v/vx9mvac0z.css';
import '../../css/k/ko6o-6b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b_mqzbbbw"/><path class="o0vcg8bqt"/><path class="vx9mvac0z"/><path class="ko6o-6b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-circle-broken" {...props}></Icon>
