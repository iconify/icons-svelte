<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6-ylwfiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z6-ylwfiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-loop-limit-duotone" {...props}></Icon>
