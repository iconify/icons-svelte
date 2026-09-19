<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e46aaylfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e46aaylfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-add-fill" {...props}></Icon>
