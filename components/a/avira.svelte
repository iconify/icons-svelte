<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr-sl2bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-sl2bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avira" {...props}></Icon>
