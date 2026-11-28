<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzki34brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzki34brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:credit-card-refresh" {...props}></Icon>
