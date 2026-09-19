<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-9m4gbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-9m4gbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-left" {...props}></Icon>
