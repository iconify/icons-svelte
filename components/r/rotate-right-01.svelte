<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndhirqc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndhirqc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-right-01" {...props}></Icon>
