<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn3jo-bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="yn3jo-bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:grunt-wordmark" {...props}></Icon>
