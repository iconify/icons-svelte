<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxg94rb_l.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/t9rd3ac0o.css';
import '../../css/u/ujpkbubht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bxg94rb_l"/><g class="ij2x_72vy"><path class="t9rd3ac0o"/><path class="ujpkbubht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flamingo" {...props}></Icon>
