<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwkk87onx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pwkk87onx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:css3" {...props}></Icon>
