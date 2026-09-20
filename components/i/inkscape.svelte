<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-oxpzahn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-oxpzahn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:inkscape" {...props}></Icon>
