<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6-ubnbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6-ubnbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list-outdent" {...props}></Icon>
