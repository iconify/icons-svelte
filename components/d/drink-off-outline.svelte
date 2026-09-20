<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orpklqf2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orpklqf2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drink-off-outline" {...props}></Icon>
