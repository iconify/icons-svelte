<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdbj31jbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdbj31jbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:navigation-line" {...props}></Icon>
