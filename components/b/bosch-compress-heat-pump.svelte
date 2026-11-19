<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbecrtbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbecrtbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bosch-compress-heat-pump" {...props}></Icon>
