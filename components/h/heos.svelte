<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eabh0cstn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eabh0cstn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:heos" {...props}></Icon>
