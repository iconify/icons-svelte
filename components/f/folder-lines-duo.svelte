<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tun7kpbmr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/d/da9v01fef.css';
import '../../css/n/n2ypo-bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tun7kpbmr"/><g class="dt0cm9dhy primary"><path class="tgy8uab8v"/><path class="da9v01fef"/><path class="n2ypo-bfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-lines-duo" {...props}></Icon>
