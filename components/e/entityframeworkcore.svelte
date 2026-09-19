<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyl5gmbif.css';
import '../../css/f/f5bhpxvdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gyl5gmbif"/><path class="f5bhpxvdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:entityframeworkcore" {...props}></Icon>
