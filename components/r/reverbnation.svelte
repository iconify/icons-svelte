<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs69evbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs69evbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:reverbnation" {...props}></Icon>
