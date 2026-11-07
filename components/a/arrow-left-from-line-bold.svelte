<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmgit0fdl.css';
import '../../css/b/bfch-tf9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmgit0fdl"/><path class="bfch-tf9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-from-line-bold" {...props}></Icon>
