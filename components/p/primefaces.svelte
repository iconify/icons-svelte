<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olglibbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olglibbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:primefaces" {...props}></Icon>
