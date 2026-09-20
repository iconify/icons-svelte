<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kr__f9beo.css';
import '../../css/t/t3pi35bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kr__f9beo"/><path class="t3pi35bue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cancel-octagon" {...props}></Icon>
