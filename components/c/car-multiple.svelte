<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0md93b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0md93b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-multiple" {...props}></Icon>
