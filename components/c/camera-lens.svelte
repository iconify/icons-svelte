<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g8qfvnbjm.css';
import '../../css/e/egfs-cciu.css';
import '../../css/z/zga1a2bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="g8qfvnbjm"/><circle class="egfs-cciu"/><path class="zga1a2bdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-lens" {...props}></Icon>
