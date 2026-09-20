<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx1141bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx1141bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cirrusci" {...props}></Icon>
