<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj4ouy93g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4ouy93g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-won-2-line" {...props}></Icon>
