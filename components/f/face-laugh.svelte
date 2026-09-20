<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux3s0mb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux3s0mb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-laugh" {...props}></Icon>
