<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s50cx-bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s50cx-bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:couchdb" {...props}></Icon>
