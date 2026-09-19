<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2ldz72eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2ldz72eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bell" {...props}></Icon>
