<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onkrl4p-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onkrl4p-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bbq-outline" {...props}></Icon>
