<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgx99j8cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dgx99j8cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ambys-dark" {...props}></Icon>
