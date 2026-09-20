<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m97iezbay.css';
import '../../css/m/mjojrgq4j.css';
import '../../css/d/dujh-y52z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m97iezbay"/><path class="mjojrgq4j"/><path class="dujh-y52z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-broken" {...props}></Icon>
