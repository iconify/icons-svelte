<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm4cb0mcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xm4cb0mcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-exclamation-solid" {...props}></Icon>
