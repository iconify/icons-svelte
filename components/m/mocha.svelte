<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhcgfebjd.css';
import '../../css/z/zmii52bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dhcgfebjd"/><path class="zmii52bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mocha" {...props}></Icon>
