<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9sro_clj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9sro_clj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-plus-fill" {...props}></Icon>
