<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm9nwob-m.css';
import '../../css/h/hnglj9b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rm9nwob-m"/><path clip-rule="evenodd" class="hnglj9b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:car-taxi-1-solid" {...props}></Icon>
