<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdw6n2bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="mdw6n2bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:image" {...props}></Icon>
