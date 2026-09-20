<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3j076bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3j076bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-2-filled" {...props}></Icon>
