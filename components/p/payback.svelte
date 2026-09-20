<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz2efpxtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz2efpxtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:payback" {...props}></Icon>
