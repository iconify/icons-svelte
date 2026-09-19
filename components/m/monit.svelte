<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbot6tbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbot6tbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:monit" {...props}></Icon>
