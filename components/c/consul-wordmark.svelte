<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk8f1vb6j.css';
import '../../css/a/ab8l0tjds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tk8f1vb6j"/><path class="ab8l0tjds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:consul-wordmark" {...props}></Icon>
