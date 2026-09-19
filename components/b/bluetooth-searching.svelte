<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-8_t8frx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-8_t8frx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bluetooth-searching" {...props}></Icon>
