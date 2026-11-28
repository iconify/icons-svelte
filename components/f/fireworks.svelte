<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a90eyi3wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a90eyi3wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fireworks" {...props}></Icon>
