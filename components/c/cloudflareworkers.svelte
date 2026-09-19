<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngo9862vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ngo9862vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cloudflareworkers" {...props}></Icon>
