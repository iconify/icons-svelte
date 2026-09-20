<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9sl6v05z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sl6v05z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-diamond-solid" {...props}></Icon>
