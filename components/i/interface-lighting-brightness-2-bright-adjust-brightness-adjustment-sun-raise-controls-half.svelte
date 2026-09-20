<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afgz_374z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="afgz_374z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-lighting-brightness-2-bright-adjust-brightness-adjustment-sun-raise-controls-half" {...props}></Icon>
