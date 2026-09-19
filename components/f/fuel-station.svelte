<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a2g9elbyt.css';
import '../../css/o/ootkfz6rc.css';
import '../../css/z/zw-iqyb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="a2g9elbyt"/><path class="ootkfz6rc"/><path class="zw-iqyb4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fuel-station" {...props}></Icon>
