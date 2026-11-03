<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx3sflbzb.css';
import '../../css/f/fntwqg-7t.css';
import '../../css/b/blgoysbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yx3sflbzb"/><path class="fntwqg-7t"/><path class="blgoysbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:homeassistant-wordmark" {...props}></Icon>
