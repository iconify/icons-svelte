<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftmf2jnxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="ftmf2jnxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pslone" {...props}></Icon>
