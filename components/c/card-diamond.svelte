<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcql0kbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcql0kbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:card-diamond" {...props}></Icon>
