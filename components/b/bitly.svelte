<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgqj3z6yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgqj3z6yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitly" {...props}></Icon>
