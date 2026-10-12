<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dba1-yhnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dba1-yhnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list" {...props}></Icon>
