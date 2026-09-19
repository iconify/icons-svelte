<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdhrlnphl.css';
import '../../css/d/drbu3zb8y.css';
import '../../css/m/mol134btx.css';
import '../../css/t/t5hp_obfp.css';
import '../../css/k/k36i95p_h.css';
import '../../css/p/pjnb8bc5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pdhrlnphl"/><path class="drbu3zb8y"/><path class="mol134btx"/><path clip-rule="evenodd" class="t5hp_obfp"/><path clip-rule="evenodd" class="k36i95p_h"/><path class="pjnb8bc5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:huggingface-wordmark" {...props}></Icon>
