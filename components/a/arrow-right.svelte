<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i52o7bbpp.css';
import '../../css/t/tpmoddcaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i52o7bbpp wm-k"/><path class="tpmoddcaw wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-right" {...props}></Icon>
