<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu1p7nb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mu1p7nb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:netbeans" {...props}></Icon>
