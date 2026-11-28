<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkk_n4bvn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tgy8uab8v.css';
import '../../css/p/p4q7_x47d.css';
import '../../css/u/udd024qri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wkk_n4bvn"/><g class="dt0cm9dhy primary"><path class="tgy8uab8v"/><path class="p4q7_x47d"/><path class="udd024qri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-search-duo" {...props}></Icon>
