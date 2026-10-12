<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkg-1fb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkg-1fb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cent" {...props}></Icon>
