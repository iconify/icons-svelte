<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlw8gbbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlw8gbbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-up-left" {...props}></Icon>
