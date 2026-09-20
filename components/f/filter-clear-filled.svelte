<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv9eqyb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv9eqyb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-clear-filled" {...props}></Icon>
