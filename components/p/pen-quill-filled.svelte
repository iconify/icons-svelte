<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfpnljh4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfpnljh4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pen-quill-filled" {...props}></Icon>
