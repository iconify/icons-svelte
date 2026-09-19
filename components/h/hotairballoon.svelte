<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0vmx-8pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":32};
const content = `<path class="k0vmx-8pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:hotairballoon" {...props}></Icon>
