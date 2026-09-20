<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp7c32rjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp7c32rjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-cnb-filled" {...props}></Icon>
