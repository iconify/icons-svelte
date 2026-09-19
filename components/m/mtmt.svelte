<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrck--npu.css';
import '../../css/a/a3kaa3-qw.css';
import '../../css/f/fhtwuabpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="mrck--npu"><path class="a3kaa3-qw"/><path class="fhtwuabpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:mtmt" {...props}></Icon>
