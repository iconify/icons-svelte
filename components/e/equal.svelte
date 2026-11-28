<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0hxmebtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0hxmebtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:equal" {...props}></Icon>
