<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxda01bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxda01bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:forward-outline" {...props}></Icon>
