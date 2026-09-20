<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jiybjcc5h.css';
import '../../css/b/bhqi51bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jiybjcc5h"/><path class="bhqi51bwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:article-duotone" {...props}></Icon>
