<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha-pt9vny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha-pt9vny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-outline" {...props}></Icon>
