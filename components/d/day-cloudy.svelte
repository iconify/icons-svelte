<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izykwd8ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="izykwd8ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:day-cloudy" {...props}></Icon>
