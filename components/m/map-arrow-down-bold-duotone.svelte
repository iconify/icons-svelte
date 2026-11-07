<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4brlnqpx.css';
import '../../css/b/bpeho1s8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4brlnqpx"/><path class="bpeho1s8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-down-bold-duotone" {...props}></Icon>
