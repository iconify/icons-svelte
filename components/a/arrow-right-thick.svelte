<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_tzujzca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_tzujzca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-thick" {...props}></Icon>
