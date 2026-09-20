<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nemk98b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nemk98b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-incoming-fill" {...props}></Icon>
