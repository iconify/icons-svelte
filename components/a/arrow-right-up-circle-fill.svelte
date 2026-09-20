<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijysev5_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijysev5_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-up-circle-fill" {...props}></Icon>
