<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h32f_itun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h32f_itun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mercurial-wordmark" {...props}></Icon>
