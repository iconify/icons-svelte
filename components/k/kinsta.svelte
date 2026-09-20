<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkhogc02b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkhogc02b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kinsta" {...props}></Icon>
