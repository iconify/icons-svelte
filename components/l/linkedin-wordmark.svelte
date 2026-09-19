<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_7p37bmf.css';
import '../../css/l/ly5qkx5wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k_7p37bmf"/><path class="ly5qkx5wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linkedin-wordmark" {...props}></Icon>
