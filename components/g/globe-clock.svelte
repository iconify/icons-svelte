<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km9rw_16t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km9rw_16t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-clock" {...props}></Icon>
