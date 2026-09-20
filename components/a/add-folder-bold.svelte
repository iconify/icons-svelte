<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suo4c_bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="suo4c_bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-folder-bold" {...props}></Icon>
