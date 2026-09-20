<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2bs-acjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2bs-acjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-keyhole-unlocked-bold" {...props}></Icon>
