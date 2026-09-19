<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phhyu2bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="phhyu2bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:protractor-wordmark" {...props}></Icon>
