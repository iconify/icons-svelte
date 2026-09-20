<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gave4vgwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gave4vgwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flint-dark" {...props}></Icon>
