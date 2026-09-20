<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km2dfdcao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km2dfdcao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hair-dress-barber-bold" {...props}></Icon>
