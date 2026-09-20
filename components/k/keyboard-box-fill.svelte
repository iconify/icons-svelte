<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1i8s8bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1i8s8bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:keyboard-box-fill" {...props}></Icon>
