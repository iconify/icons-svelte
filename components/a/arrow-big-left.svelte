<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-xvnsbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-xvnsbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-big-left" {...props}></Icon>
