<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvig-vcjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cvig-vcjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:octopus-deploy" {...props}></Icon>
