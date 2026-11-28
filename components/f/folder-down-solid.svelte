<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u07v3c-nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u07v3c-nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-down-solid" {...props}></Icon>
