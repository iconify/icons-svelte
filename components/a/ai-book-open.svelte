<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ni1ex1sbr.css';
import '../../css/l/ldpo4n3qb.css';
import '../../css/u/ubtuxebtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ni1ex1sbr"/><path class="ldpo4n3qb"/><path class="ubtuxebtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-book-open" {...props}></Icon>
