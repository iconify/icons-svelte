<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxusby2tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxusby2tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-from-dot-fill" {...props}></Icon>
