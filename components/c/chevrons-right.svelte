<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd83xkb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd83xkb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevrons-right" {...props}></Icon>
