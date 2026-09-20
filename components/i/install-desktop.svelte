<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfefj9bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfefj9bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install-desktop" {...props}></Icon>
