<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6wh3497s.css';
import '../../css/z/zcfsn21nh.css';
import '../../css/z/zsn_dkb-f.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/p/prgx4tbuc.css';
import '../../css/y/yt42wrtkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="z6wh3497s"/><path class="zcfsn21nh"/><path class="zsn_dkb-f"/><g class="jn8qy4bru"><path class="prgx4tbuc"/><path class="yt42wrtkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:euro-banknote" {...props}></Icon>
