<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/njv_4__ad.css';
import '../../css/o/o2k9am28j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="njv_4__ad"/><path class="o2k9am28j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-warning-3" {...props}></Icon>
