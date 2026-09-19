<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yk6ie_5mn.css';
import '../../css/r/rjd7ks-cj.css';
import '../../css/o/o5x5qit7g.css';
import '../../css/c/c3quwww_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="yk6ie_5mn"/><path clip-rule="evenodd" class="rjd7ks-cj"/><path class="o5x5qit7g"/><path clip-rule="evenodd" class="c3quwww_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:highlighter-outline" {...props}></Icon>
