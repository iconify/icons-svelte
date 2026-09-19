<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rjbttgbsa.css';
import '../../css/v/vzr9tvb2h.css';
import '../../css/z/zbbn00bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rjbttgbsa"/><path class="vzr9tvb2h"/><path class="zbbn00bvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:favourite-window" {...props}></Icon>
