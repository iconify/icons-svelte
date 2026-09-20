<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_cyjh5hd.css';
import '../../css/r/r8bd01bug.css';
import '../../css/d/d8mvshbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="r8bd01bug"/><path class="d8mvshbpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-vert-square-line" {...props}></Icon>
