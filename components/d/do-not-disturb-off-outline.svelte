<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmh-avb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmh-avb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:do-not-disturb-off-outline" {...props}></Icon>
