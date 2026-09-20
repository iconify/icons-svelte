<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqosdg6xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqosdg6xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-left-linear" {...props}></Icon>
