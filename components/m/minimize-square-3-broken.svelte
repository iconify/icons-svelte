<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vv3m6lbyb.css';
import '../../css/r/r9eucsbka.css';
import '../../css/v/v6xozwwqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vv3m6lbyb"/><path class="r9eucsbka"/><path class="v6xozwwqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-3-broken" {...props}></Icon>
