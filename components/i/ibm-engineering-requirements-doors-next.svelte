<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fklgh1ehi.css';
import '../../css/w/wszt4c0fp.css';
import '../../css/t/th5rvlnyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fklgh1ehi"/><circle class="wszt4c0fp"/><path class="th5rvlnyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-requirements-doors-next" {...props}></Icon>
