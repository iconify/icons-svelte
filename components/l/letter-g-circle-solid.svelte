<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh3g_jboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3g_jboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-circle-solid" {...props}></Icon>
