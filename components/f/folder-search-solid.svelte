<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/andh5bc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="andh5bc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-search-solid" {...props}></Icon>
