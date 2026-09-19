<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_1ewccfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f_1ewccfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-remove-stroke-12" {...props}></Icon>
