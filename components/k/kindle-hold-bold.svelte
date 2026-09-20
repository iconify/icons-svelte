<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r84escbrd.css';
import '../../css/q/qffwwpzrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r84escbrd"/><path class="qffwwpzrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:kindle-hold-bold" {...props}></Icon>
