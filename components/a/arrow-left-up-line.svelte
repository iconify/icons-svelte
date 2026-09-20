<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcn5smb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcn5smb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-up-line" {...props}></Icon>
