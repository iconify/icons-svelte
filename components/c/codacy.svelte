<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbyeo8h9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbyeo8h9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codacy" {...props}></Icon>
