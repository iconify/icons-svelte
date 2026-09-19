<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alwq3rdnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="alwq3rdnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:horizon" {...props}></Icon>
