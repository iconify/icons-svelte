<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txz6rnsnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="txz6rnsnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jamstack-wordmark" {...props}></Icon>
