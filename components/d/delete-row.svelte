<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu8cjbcaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu8cjbcaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-row" {...props}></Icon>
