<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmd2sgb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmd2sgb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-down-fill" {...props}></Icon>
