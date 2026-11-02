<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtu5bdc_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtu5bdc_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rain-fill" {...props}></Icon>
