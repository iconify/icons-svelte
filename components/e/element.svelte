<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jar4abbwg.css';
import '../../css/l/legm6kbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jar4abbwg"/><path class="legm6kbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:element" {...props}></Icon>
