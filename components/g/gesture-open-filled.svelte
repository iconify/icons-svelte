<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f35lopb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f35lopb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-open-filled" {...props}></Icon>
