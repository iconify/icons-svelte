<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkjw91b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkjw91b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:christmas-wreath" {...props}></Icon>
