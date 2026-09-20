<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-1zhdc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-1zhdc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:risc-v" {...props}></Icon>
