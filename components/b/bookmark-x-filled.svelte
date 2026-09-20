<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efs0dg7sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efs0dg7sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark-x-filled" {...props}></Icon>
