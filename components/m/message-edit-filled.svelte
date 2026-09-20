<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxbu_zb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxbu_zb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-edit-filled" {...props}></Icon>
