<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ie2v4kb6j.css';
import '../../css/i/id7d1qbgo.css';
import '../../css/x/xraqxobnj.css';
import '../../css/l/l9paz7bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ie2v4kb6j"/><path class="id7d1qbgo"/><path class="xraqxobnj"/><path class="l9paz7bvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:croissant-duotone" {...props}></Icon>
