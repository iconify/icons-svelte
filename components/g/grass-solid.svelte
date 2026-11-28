<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x67qmvbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x67qmvbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grass-solid" {...props}></Icon>
