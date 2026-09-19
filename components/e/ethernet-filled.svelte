<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk_ayjb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk_ayjb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ethernet-filled" {...props}></Icon>
