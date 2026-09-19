<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmw38b5pn.css';
import '../../css/z/zse_r2bij.css';
import '../../css/c/cs-uxhb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmw38b5pn"/><path class="zse_r2bij"/><circle class="cs-uxhb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flashlight" {...props}></Icon>
