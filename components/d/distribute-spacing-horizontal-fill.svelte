<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi2dzkbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi2dzkbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-horizontal-fill" {...props}></Icon>
