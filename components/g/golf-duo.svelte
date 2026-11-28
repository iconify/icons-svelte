<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc5eqnq-v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/md4di2vlv.css';
import '../../css/h/hraeq983i.css';
import '../../css/u/uvb-1pbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zc5eqnq-v"/><g class="dt0cm9dhy primary"><path class="md4di2vlv"/><path class="hraeq983i"/><path class="uvb-1pbtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:golf-duo" {...props}></Icon>
