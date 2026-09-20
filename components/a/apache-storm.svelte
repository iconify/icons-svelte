<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4l4iwb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4l4iwb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-storm" {...props}></Icon>
