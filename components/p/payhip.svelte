<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su0grkb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su0grkb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:payhip" {...props}></Icon>
