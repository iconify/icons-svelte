<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/f/f3xl7f2bt.css';
import '../../css/a/a2jwblbfm.css';
import '../../css/j/joeryvb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="f3xl7f2bt"/><path class="a2jwblbfm"/><path class="joeryvb2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-error-light" {...props}></Icon>
