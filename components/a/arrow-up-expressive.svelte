<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu6ptwbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu6ptwbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-up-expressive" {...props}></Icon>
