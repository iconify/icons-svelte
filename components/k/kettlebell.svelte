<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg2p0hbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg2p0hbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:kettlebell" {...props}></Icon>
