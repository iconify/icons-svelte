<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv118o9ri.css';
import '../../css/w/wrw3ncchb.css';
import '../../css/c/ckd-ucc8g.css';
import '../../css/s/s-8_n-eys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fv118o9ri"/><path class="wrw3ncchb"/><path class="ckd-ucc8g"/><path class="s-8_n-eys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cargo-drone-20" {...props}></Icon>
