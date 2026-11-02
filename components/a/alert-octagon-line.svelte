<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym9ym958l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym9ym958l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-octagon-line" {...props}></Icon>
