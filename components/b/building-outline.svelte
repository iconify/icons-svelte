<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cbfmji0-x.css';
import '../../css/t/ttexwac3y.css';
import '../../css/e/efdc1gb8g.css';
import '../../css/b/bp87d8bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="cbfmji0-x"/><path clip-rule="evenodd" class="ttexwac3y"/><path class="efdc1gb8g"/><path clip-rule="evenodd" class="bp87d8bgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-outline" {...props}></Icon>
