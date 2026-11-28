<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v55azh8hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v55azh8hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:air-conditioner" {...props}></Icon>
