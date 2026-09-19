<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nro_fcb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nro_fcb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:first-aid-kit" {...props}></Icon>
