<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/k/kl149rbvc.css';
import '../../css/c/cnrn66j_x.css';
import '../../css/g/gkp1rfbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="kl149rbvc"/><path class="cnrn66j_x"/><path class="gkp1rfbjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:orbit" {...props}></Icon>
