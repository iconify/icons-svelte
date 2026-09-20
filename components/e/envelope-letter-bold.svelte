<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6r356-xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6r356-xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:envelope-letter-bold" {...props}></Icon>
