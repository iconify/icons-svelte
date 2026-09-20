<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvc9u6bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvc9u6bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:diamond" {...props}></Icon>
