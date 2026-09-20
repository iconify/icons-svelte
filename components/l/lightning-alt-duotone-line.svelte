<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dih714bjx.css';
import '../../css/e/elefkcc4m.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGXEoPXcvl"><g class="ft5dv1b6b"><path class="dih714bjx"/><path class="elefkcc4m"/></g></mask></defs><path mask="url(#SVGXEoPXcvl)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lightning-alt-duotone-line" {...props}></Icon>
