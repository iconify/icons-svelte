<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksjezmbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ksjezmbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cakephp" {...props}></Icon>
