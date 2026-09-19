<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvilx1q3c.css';
import '../../css/p/pqwcjgxcc.css';
import '../../css/x/x9ylqsbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="pqwcjgxcc"/><path class="x9ylqsbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:book-open" {...props}></Icon>
