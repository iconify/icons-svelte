<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/n/ne1xewb3x.css';
import '../../css/z/zkcdoy1on.css';
import '../../css/m/msh9cmbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 6 13)" class="ne1xewb3x"/><rect transform="rotate(-90 17 12)" class="zkcdoy1on"/><path class="msh9cmbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-alt" {...props}></Icon>
