<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgenbsbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgenbsbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-adore" {...props}></Icon>
