<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seyos_bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seyos_bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:database-search-solid" {...props}></Icon>
