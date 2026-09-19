<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aboskhb3q.css';
import '../../css/h/hie0ikbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aboskhb3q"/><path class="hie0ikbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:prometheus-wordmark" {...props}></Icon>
