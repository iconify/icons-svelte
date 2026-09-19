<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3o3ldbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3o3ldbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:medical-sharp" {...props}></Icon>
