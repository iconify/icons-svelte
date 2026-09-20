<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4kosrbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4kosrbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-tapd-filled" {...props}></Icon>
