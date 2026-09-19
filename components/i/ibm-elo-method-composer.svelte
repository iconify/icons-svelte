<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvtb7tb3p.css';
import '../../css/g/gor6sh79f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cvtb7tb3p"/><path class="gor6sh79f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-elo-method-composer" {...props}></Icon>
