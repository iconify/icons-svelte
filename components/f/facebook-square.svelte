<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-dthd25w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-dthd25w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:facebook-square" {...props}></Icon>
