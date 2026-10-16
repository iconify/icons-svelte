<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbl98olvj.css';
import '../../css/d/drqiwqb8a.css';
import '../../css/o/o22z116ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nbl98olvj"/><path class="drqiwqb8a"/><path class="o22z116ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pelton-wheel-48" {...props}></Icon>
