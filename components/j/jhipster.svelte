<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebmrnmb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ebmrnmb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jhipster" {...props}></Icon>
