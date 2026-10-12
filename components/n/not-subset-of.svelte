<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4akcoble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4akcoble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:not-subset-of" {...props}></Icon>
