<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poiit8bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poiit8bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-out-solid" {...props}></Icon>
