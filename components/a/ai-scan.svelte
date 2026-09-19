<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp975jbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp975jbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-scan" {...props}></Icon>
