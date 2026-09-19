<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftf0vwb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ftf0vwb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nhibernate-wordmark" {...props}></Icon>
