<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sumq48c7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sumq48c7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:air-canada" {...props}></Icon>
