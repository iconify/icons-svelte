<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o71bscr7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o71bscr7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-details-filled" {...props}></Icon>
