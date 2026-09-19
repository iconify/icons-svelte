<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiv92mbuz.css';
import '../../css/f/fu98lubud.css';
import '../../css/o/o32ixwgun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="tiv92mbuz"/><path class="fu98lubud"/><path class="o32ixwgun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-view" {...props}></Icon>
