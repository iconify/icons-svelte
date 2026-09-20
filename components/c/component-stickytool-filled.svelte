<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0ynevbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0ynevbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-stickytool-filled" {...props}></Icon>
