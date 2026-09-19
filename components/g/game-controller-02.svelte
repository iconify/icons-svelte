<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/ryy00cbat.css';
import '../../css/j/jz5umcc9b.css';
import '../../css/v/v4a588b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ryy00cbat"/><path class="jz5umcc9b"/><path class="v4a588b4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:game-controller-02" {...props}></Icon>
