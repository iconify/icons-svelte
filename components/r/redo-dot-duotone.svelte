<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf1hbcc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wf1hbcc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:redo-dot-duotone" {...props}></Icon>
