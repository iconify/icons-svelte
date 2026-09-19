<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5mhlcug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="un5mhlcug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:processing" {...props}></Icon>
