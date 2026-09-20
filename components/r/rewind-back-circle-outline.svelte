<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeiamk_lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeiamk_lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-back-circle-outline" {...props}></Icon>
