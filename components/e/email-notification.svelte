<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/caeecabqw.css';
import '../../css/e/eti1awbyg.css';
import '../../css/l/lm2y_hbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="caeecabqw"/><path class="eti1awbyg"/><circle class="lm2y_hbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:email-notification" {...props}></Icon>
