<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwuu-kkit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwuu-kkit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-line-fill" {...props}></Icon>
