<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynxabotvb.css';
import '../../css/n/nk5kckb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ynxabotvb"/><path class="nk5kckb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:antlr" {...props}></Icon>
