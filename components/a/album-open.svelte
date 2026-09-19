<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zmwq3spqd.css';
import '../../css/t/tqywrzb5u.css';
import '../../css/t/tdq4jhbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zmwq3spqd"/><path class="tqywrzb5u"/><path class="tdq4jhbph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:album-open" {...props}></Icon>
