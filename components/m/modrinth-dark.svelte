<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5v0c1bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5v0c1bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:modrinth-dark" {...props}></Icon>
