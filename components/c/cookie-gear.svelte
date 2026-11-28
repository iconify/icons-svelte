<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlugd1bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlugd1bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cookie-gear" {...props}></Icon>
