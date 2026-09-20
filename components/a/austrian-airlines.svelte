<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whfl3kb-r.css';
import '../../css/l/laz58e6cn.css';
import '../../css/j/jmtoiebca.css';
import '../../css/s/so4w25-jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":499.3,"height":72};
const content = `<path clip-rule="evenodd" class="whfl3kb-r"/><path class="laz58e6cn"/><path clip-rule="evenodd" class="jmtoiebca"/><path clip-rule="evenodd" class="so4w25-jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:austrian-airlines" {...props}></Icon>
