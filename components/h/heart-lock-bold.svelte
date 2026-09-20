<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk93pacvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk93pacvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-lock-bold" {...props}></Icon>
