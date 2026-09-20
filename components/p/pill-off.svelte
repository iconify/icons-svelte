<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkqbo8bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkqbo8bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pill-off" {...props}></Icon>
