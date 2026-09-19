<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/t/trlth4bch.css';
import '../../css/n/nf1dv4jjz.css';
import '../../css/i/io8in3baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="h_l78yaxm"/><path class="trlth4bch"/><path class="nf1dv4jjz"/><path class="io8in3baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-02" {...props}></Icon>
