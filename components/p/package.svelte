<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_2ijbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc_2ijbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package" {...props}></Icon>
