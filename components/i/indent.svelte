<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oirxshbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="oirxshbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:indent" {...props}></Icon>
