<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e8pb5pdno.css';
import '../../css/j/jxst5l4bq.css';
import '../../css/i/in4dbducl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e8pb5pdno"/><path class="jxst5l4bq"/><path class="in4dbducl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alien-02" {...props}></Icon>
