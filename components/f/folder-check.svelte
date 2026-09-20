<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0m0t4b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0m0t4b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-check" {...props}></Icon>
