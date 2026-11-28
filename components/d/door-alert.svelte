<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw14teb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw14teb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:door-alert" {...props}></Icon>
