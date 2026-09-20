<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rjhbwvqze.css';
import '../../css/b/bm295x_5y.css';
import '../../css/k/kp4yyebmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rjhbwvqze"/><path class="bm295x_5y"/><path class="kp4yyebmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:email-attachment-image" {...props}></Icon>
