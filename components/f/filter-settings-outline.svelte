<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulgl77hkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulgl77hkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-settings-outline" {...props}></Icon>
