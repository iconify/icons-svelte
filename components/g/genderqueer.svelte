<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzlkm6bkg.css';
import '../../css/u/u65lgdc6d.css';
import '../../css/m/msy7dmbdy.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nzlkm6bkg"/><path class="u65lgdc6d"/><path class="msy7dmbdy"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:genderqueer" {...props}></Icon>
