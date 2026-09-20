<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9fr2gbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9fr2gbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:box-usd-solid" {...props}></Icon>
