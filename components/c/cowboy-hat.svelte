<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hvb16ibtn.css';
import '../../css/j/j9lx0zklz.css';
import '../../css/e/erhl3ib4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hvb16ibtn"/><path class="j9lx0zklz"/><path class="erhl3ib4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cowboy-hat" {...props}></Icon>
