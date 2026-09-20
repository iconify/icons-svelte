<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azdczlbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azdczlbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-80" {...props}></Icon>
