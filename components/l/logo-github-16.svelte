<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtge9yb3h.css';
import '../../css/z/z_6r0ejay.css';
import '../../css/n/nnagpvtvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":16};
const content = `<path class="gtge9yb3h"/><path class="z_6r0ejay"/><path class="nnagpvtvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:logo-github-16" {...props}></Icon>
