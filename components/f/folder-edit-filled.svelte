<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjnfe56w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxjnfe56w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-edit-filled" {...props}></Icon>
