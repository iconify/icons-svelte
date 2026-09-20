<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smb8bhb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smb8bhb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-arrow-up-outline" {...props}></Icon>
