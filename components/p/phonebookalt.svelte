<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg8u_7bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fg8u_7bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phonebookalt" {...props}></Icon>
