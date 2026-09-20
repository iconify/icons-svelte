<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wav--fbep.css';
import '../../css/p/p1jwip47c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wav--fbep"/><path clip-rule="evenodd" class="p1jwip47c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bar-chart-4" {...props}></Icon>
