<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pz4a6t63l.css';
import '../../css/h/h4-__3b9e.css';
import '../../css/j/j2qre1brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pz4a6t63l"/><path class="h4-__3b9e"/><path class="j2qre1brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bin-plus-in" {...props}></Icon>
