<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqfv9_bht.css';
import '../../css/g/g2z0o6bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqfv9_bht"/><path class="g2z0o6bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-from-line-bold-duotone" {...props}></Icon>
