<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4gl7mltg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f4gl7mltg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:couchdb" {...props}></Icon>
