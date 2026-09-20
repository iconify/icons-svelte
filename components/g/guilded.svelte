<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ff85b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ff85b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:guilded" {...props}></Icon>
