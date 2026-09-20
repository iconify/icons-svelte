<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h695rk-bi.css';
import '../../css/a/aealofbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h695rk-bi"/><path class="aealofbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-dollar-fill" {...props}></Icon>
