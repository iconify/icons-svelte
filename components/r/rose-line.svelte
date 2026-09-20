<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buu_4mbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buu_4mbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rose-line" {...props}></Icon>
