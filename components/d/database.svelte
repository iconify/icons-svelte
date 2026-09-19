<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/a/a06nqacsr.css';
import '../../css/t/trlth4bch.css';
import '../../css/k/k_yyil5ms.css';
import '../../css/n/nf1dv4jjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="h_l78yaxm"/><path class="a06nqacsr"/><path class="trlth4bch"/><path class="k_yyil5ms"/><path class="nf1dv4jjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database" {...props}></Icon>
