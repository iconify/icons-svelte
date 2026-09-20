<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0andfb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0andfb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:flora" {...props}></Icon>
