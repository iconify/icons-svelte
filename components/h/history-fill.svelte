<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqf70vd_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqf70vd_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-fill" {...props}></Icon>
