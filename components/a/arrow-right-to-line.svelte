<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/n99c7obse.css';
import '../../css/a/av_m4nb6v.css';
import '../../css/u/ul75skb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="n99c7obse wm-shadow"/><path class="av_m4nb6v wm-shadow"/><path class="ul75skb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:arrow-right-to-line" {...props}></Icon>
