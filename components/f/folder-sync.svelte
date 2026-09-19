<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcuk2y6ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuk2y6ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-sync" {...props}></Icon>
