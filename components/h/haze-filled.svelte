<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbh13sb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbh13sb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:haze-filled" {...props}></Icon>
