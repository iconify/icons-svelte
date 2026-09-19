<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf8q0slyc.css';
import '../../css/u/ukroeg7me.css';
import '../../css/e/emfunmbju.css';
import '../../css/f/f76sgsh0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf8q0slyc"/><path class="ukroeg7me"/><path class="emfunmbju"/><path class="f76sgsh0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:finger-print" {...props}></Icon>
