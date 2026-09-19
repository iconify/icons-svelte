<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkelfkb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkelfkb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:kidneys-24px" {...props}></Icon>
