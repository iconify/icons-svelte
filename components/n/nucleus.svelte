<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6qanlb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l6qanlb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:nucleus" {...props}></Icon>
