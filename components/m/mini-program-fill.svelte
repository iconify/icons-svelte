<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwniernpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwniernpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mini-program-fill" {...props}></Icon>
