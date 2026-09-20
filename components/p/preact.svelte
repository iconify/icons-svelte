<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfo6y1b6f.css';
import '../../css/s/sflhpq2ep.css';
import '../../css/d/dy0pnwb7i.css';
import '../../css/a/abbea4hvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":296};
const content = `<path class="zfo6y1b6f"/><path class="sflhpq2ep"/><path class="dy0pnwb7i"/><path class="abbea4hvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:preact" {...props}></Icon>
