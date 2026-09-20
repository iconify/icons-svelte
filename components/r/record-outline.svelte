<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb5y06but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb5y06but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:record-outline" {...props}></Icon>
