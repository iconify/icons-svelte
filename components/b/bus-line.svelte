<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3g2j8bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3g2j8bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-line" {...props}></Icon>
