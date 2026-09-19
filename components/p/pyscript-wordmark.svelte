<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzs4d4blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zzs4d4blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pyscript-wordmark" {...props}></Icon>
