<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdmdb_bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdmdb_bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-child" {...props}></Icon>
