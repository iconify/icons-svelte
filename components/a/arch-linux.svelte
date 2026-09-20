<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdglxdd3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdglxdd3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arch-linux" {...props}></Icon>
