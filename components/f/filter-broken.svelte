<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbc3x4ajk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbc3x4ajk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-broken" {...props}></Icon>
