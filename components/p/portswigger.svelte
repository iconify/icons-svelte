<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtd6h5b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtd6h5b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:portswigger" {...props}></Icon>
