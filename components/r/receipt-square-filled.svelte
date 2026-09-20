<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2h2kacte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2h2kacte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt-square-filled" {...props}></Icon>
