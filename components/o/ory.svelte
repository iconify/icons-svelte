<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps7pixbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps7pixbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ory" {...props}></Icon>
