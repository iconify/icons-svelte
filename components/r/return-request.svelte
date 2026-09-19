<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t47auzzbf.css';
import '../../css/g/g6-87db_q.css';
import '../../css/f/fykrk8b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t47auzzbf"/><path class="g6-87db_q"/><path class="fykrk8b7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:return-request" {...props}></Icon>
