<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwm0kfbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwm0kfbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rewe" {...props}></Icon>
