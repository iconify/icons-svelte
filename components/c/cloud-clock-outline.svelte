<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avzubmfsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avzubmfsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-clock-outline" {...props}></Icon>
