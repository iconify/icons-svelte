<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqwq1d4qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqwq1d4qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:campaign-monitor" {...props}></Icon>
