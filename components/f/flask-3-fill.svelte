<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbdd1oz_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbdd1oz_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flask-3-fill" {...props}></Icon>
