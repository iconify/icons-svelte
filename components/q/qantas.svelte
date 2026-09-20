<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gds9jyqsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gds9jyqsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qantas" {...props}></Icon>
