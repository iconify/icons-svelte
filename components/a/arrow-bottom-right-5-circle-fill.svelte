<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzbumwr0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzbumwr0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-5-circle-fill" {...props}></Icon>
