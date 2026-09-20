<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leuna0b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leuna0b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:epson" {...props}></Icon>
