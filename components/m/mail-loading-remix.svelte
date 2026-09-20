<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_982bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in_982bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mail-loading-remix" {...props}></Icon>
