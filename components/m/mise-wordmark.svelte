<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0rs67bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c0rs67bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mise-wordmark" {...props}></Icon>
