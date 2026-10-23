<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbc2rh_nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbc2rh_nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:inspection-panel" {...props}></Icon>
