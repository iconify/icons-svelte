<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkx8at11b.css';
import '../../css/w/wsq0amysy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jkx8at11b"/><path class="wsq0amysy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:monogame-wordmark" {...props}></Icon>
