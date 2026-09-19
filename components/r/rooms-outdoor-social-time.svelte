<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc-uvi3wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc-uvi3wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-outdoor-social-time" {...props}></Icon>
