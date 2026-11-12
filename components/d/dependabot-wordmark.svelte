<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf6tnbc7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nf6tnbc7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:dependabot-wordmark" {...props}></Icon>
