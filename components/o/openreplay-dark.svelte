<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/l/l9wbs_y1i.css';
import '../../css/b/bjwamubhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<g class="n1mjunbsu"><path class="l9wbs_y1i"/><path class="bjwamubhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openreplay-dark" {...props}></Icon>
