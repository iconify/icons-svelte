<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5b9vw8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ta5b9vw8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:day-snow" {...props}></Icon>
