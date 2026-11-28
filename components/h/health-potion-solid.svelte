<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu-0zabiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-0zabiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:health-potion-solid" {...props}></Icon>
