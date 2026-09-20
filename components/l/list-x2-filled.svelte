<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5i68obbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5i68obbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-x2-filled" {...props}></Icon>
