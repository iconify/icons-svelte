<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr006pb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr006pb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-stack-broken" {...props}></Icon>
