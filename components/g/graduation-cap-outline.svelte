<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oobgrbcdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oobgrbcdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:graduation-cap-outline" {...props}></Icon>
