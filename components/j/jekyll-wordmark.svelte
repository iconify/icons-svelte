<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oik34rbfa.css';
import '../../css/i/ifrdxluft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oik34rbfa"/><path class="ifrdxluft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jekyll-wordmark" {...props}></Icon>
