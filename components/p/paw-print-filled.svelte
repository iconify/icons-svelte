<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui9sstfns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui9sstfns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paw-print-filled" {...props}></Icon>
