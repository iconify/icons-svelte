<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jdby9gq-h.css';
import '../../css/o/o0rbffbmi.css';
import '../../css/i/i4dcgmbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jdby9gq-h"/><path class="o0rbffbmi"/><path class="i4dcgmbin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-lock-broken" {...props}></Icon>
