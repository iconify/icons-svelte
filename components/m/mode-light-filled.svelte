<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s57kuzu5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="s57kuzu5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mode-light-filled" {...props}></Icon>
