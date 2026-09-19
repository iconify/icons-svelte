<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lo92hvbun.css';
import '../../css/u/u4sxwwy9k.css';
import '../../css/c/cqsfoebtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lo92hvbun"/><path class="u4sxwwy9k"/><path class="cqsfoebtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panel-left-right-dashed" {...props}></Icon>
