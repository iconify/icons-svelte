<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go6x9hbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go6x9hbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-amazon" {...props}></Icon>
