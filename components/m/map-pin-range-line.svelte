<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jybtk96am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jybtk96am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-range-line" {...props}></Icon>
