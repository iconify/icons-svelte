<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-imowbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-imowbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flight-takeoff-fill" {...props}></Icon>
