<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6mstu8gp.css';
import '../../css/h/hplljm8we.css';
import '../../css/v/v96in2bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s6mstu8gp"><path class="hplljm8we"/><path class="v96in2bls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:automl-natural-language" {...props}></Icon>
