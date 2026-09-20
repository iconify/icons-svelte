<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpkopwb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpkopwb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:earphone-filled" {...props}></Icon>
