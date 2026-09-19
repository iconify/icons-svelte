<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aisklebme.css';
import '../../css/z/z6pi86s9p.css';
import '../../css/p/p_7ey5koq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="aisklebme"/><path class="z6pi86s9p"/><path class="p_7ey5koq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:radio-outline" {...props}></Icon>
