<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ayuuiqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ayuuiqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list-in" {...props}></Icon>
