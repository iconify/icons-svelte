<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2rcctbrf.css';
import '../../css/d/d6xs-gxot.css';
import '../../css/o/o7pw7f3gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2rcctbrf"/><circle transform="rotate(-180 11 11)" class="d6xs-gxot"/><path class="o7pw7f3gm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:pen-light" {...props}></Icon>
