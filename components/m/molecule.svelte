<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8zf7cb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8zf7cb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:molecule" {...props}></Icon>
