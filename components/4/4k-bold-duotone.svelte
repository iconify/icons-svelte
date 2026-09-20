<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0p-2pbst.css';
import '../../css/e/efoiiwh-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0p-2pbst"/><path class="efoiiwh-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:4k-bold-duotone" {...props}></Icon>
