<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx-1oj1vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cx-1oj1vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:medal-solid" {...props}></Icon>
