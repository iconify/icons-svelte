<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfv63-bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfv63-bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-linear" {...props}></Icon>
