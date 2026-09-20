<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohmcow45c.css';
import '../../css/e/emp3rxbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmcow45c"/><path class="emp3rxbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hmnd" {...props}></Icon>
