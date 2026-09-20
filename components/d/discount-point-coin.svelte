<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gats52bea.css';
import '../../css/f/fkfx22b0z.css';
import '../../css/u/ui-jy_46p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gats52bea"/><path class="fkfx22b0z"/><path class="ui-jy_46p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:discount-point-coin" {...props}></Icon>
