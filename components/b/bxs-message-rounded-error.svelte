<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aikme3bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aikme3bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-rounded-error" {...props}></Icon>
