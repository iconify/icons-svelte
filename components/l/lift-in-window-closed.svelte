<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc557rb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc557rb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lift-in-window-closed" {...props}></Icon>
