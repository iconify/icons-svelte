<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxz-jybmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yxz-jybmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-5-seconds-back-outline" {...props}></Icon>
