<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzt3wp_aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uzt3wp_aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ember-wordmark" {...props}></Icon>
