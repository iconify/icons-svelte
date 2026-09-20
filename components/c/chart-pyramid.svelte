<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvuv9-98d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvuv9-98d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-pyramid" {...props}></Icon>
