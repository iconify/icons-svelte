<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li3cosb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="li3cosb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:compress" {...props}></Icon>
