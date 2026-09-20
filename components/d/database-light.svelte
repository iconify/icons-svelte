<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/aayufjbdt.css';
import '../../css/z/zzkgp--je.css';
import '../../css/g/gg_6g8wpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><ellipse class="aayufjbdt"/><path class="zzkgp--je"/><path class="gg_6g8wpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:database-light" {...props}></Icon>
