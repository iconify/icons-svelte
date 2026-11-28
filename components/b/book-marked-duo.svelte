<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oipivpcyv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mdipw5bzh.css';
import '../../css/m/m1ue8zbct.css';
import '../../css/g/gvvxt_2nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oipivpcyv secondary"/><g class="dt0cm9dhy primary"><path class="mdipw5bzh"/><path class="m1ue8zbct"/><path class="gvvxt_2nw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-marked-duo" {...props}></Icon>
