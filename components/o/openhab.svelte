<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxy_aib7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxy_aib7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openhab" {...props}></Icon>
