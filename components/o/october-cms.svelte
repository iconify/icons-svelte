<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhfdrr6ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhfdrr6ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:october-cms" {...props}></Icon>
