<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsim1g_de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsim1g_de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-wide-narrow-fill" {...props}></Icon>
