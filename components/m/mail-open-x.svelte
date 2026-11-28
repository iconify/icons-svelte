<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suo3iwr-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suo3iwr-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-open-x" {...props}></Icon>
