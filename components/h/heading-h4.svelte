<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gegs72a6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gegs72a6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:heading-h4" {...props}></Icon>
