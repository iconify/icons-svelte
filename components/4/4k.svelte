<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pccepgoye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pccepgoye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:4k" {...props}></Icon>
