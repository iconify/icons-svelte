<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo5-s_s3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo5-s_s3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:check-unread-01" {...props}></Icon>
