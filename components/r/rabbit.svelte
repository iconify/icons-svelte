<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvt0s3njn.css';
import '../../css/v/vmr_zhb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvt0s3njn"/><path class="vmr_zhb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rabbit" {...props}></Icon>
