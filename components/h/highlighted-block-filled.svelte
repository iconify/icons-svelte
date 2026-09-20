<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjumr4box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjumr4box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:highlighted-block-filled" {...props}></Icon>
