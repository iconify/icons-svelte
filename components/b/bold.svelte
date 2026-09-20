<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2kt53bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2kt53bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bold" {...props}></Icon>
