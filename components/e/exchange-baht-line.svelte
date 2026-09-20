<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8goynb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8goynb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-baht-line" {...props}></Icon>
