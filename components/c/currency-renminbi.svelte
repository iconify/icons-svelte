<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f76voxbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f76voxbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-renminbi" {...props}></Icon>
