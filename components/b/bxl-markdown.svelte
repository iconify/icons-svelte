<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to_jppbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to_jppbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-markdown" {...props}></Icon>
