<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/v/vn8sbhbcq.css';
import '../../css/e/e6yrqacor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="vn8sbhbcq"/><path class="e6yrqacor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:docsearch" {...props}></Icon>
