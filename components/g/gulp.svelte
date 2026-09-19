<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aep8f2bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="aep8f2bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gulp" {...props}></Icon>
