<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms5-ntotx.css';
import '../../css/s/s3l-i3nyz.css';
import '../../css/e/evbbf8bxp.css';
import '../../css/w/wplu9ikca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5-ntotx wm-k"/><path class="s3l-i3nyz wm-a"/><path class="evbbf8bxp wm-a"/><path class="wm-a wplu9ikca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:loader" {...props}></Icon>
