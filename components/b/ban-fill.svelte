<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv7eq8pia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7eq8pia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ban-fill" {...props}></Icon>
