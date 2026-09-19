<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn51ebbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dn51ebbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlem" {...props}></Icon>
