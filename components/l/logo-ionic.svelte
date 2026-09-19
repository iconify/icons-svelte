<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5piqkb1i.css';
import '../../css/m/ms1j4bchs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5piqkb1i"/><path class="ms1j4bchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-ionic" {...props}></Icon>
