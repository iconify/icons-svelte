<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjp3d4bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjp3d4bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:butterfly" {...props}></Icon>
