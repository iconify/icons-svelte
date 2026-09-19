<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgsxwe0_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lgsxwe0_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:drum-steelpan" {...props}></Icon>
