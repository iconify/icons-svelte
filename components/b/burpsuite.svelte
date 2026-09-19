<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g37freb4x.css';
import '../../css/c/ck8n3ib1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g37freb4x"/><path class="ck8n3ib1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:burpsuite" {...props}></Icon>
