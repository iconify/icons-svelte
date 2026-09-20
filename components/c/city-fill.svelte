<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlx-g_bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlx-g_bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:city-fill" {...props}></Icon>
