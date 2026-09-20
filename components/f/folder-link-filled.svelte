<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9oa3ab1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9oa3ab1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-link-filled" {...props}></Icon>
