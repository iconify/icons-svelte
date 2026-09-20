<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goyx2cb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goyx2cb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:erpnext" {...props}></Icon>
