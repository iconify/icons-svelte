<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0fjq6bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g0fjq6bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opensuse" {...props}></Icon>
