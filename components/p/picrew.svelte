<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la7ujjqez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la7ujjqez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:picrew" {...props}></Icon>
