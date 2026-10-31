<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ephwb-o.css';
import '../../css/p/peudg--ud.css';
import '../../css/w/wx9y-fb7s.css';
import '../../css/u/u69-q7bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="x7ephwb-o"/><path class="peudg--ud"/><path class="wx9y-fb7s"/><path class="u69-q7bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:india" {...props}></Icon>
