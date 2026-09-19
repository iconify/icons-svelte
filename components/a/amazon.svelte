<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg8exbb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="xg8exbb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:amazon" {...props}></Icon>
