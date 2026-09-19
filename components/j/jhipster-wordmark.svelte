<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncv5qsbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ncv5qsbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jhipster-wordmark" {...props}></Icon>
