<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/epn4iybfc.css';
import '../../css/u/uk-710b6s.css';
import '../../css/g/g-doz0n7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="epn4iybfc"/><path class="uk-710b6s"/><path class="g-doz0n7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-square-duo" {...props}></Icon>
