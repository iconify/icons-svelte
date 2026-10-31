<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clymk1bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clymk1bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-checklist-duotone-round" {...props}></Icon>
