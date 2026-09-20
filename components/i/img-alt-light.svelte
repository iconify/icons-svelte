<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/j/jwum6hb4u.css';
import '../../css/b/bakchowuc.css';
import '../../css/y/y_fwr5blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="jwum6hb4u"/><path class="bakchowuc"/><path class="y_fwr5blk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:img-alt-light" {...props}></Icon>
