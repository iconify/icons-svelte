<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvyfft4ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="yvyfft4ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:knowledge-base-26" {...props}></Icon>
