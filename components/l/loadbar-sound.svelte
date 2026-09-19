<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn4baw61j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn4baw61j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:loadbar-sound" {...props}></Icon>
