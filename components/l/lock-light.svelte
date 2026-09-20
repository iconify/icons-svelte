<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ygox79bep.css';
import '../../css/z/zy_fdbc1g.css';
import '../../css/j/jbrxmkbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ygox79bep"/><path class="zy_fdbc1g"/><path class="jbrxmkbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lock-light" {...props}></Icon>
