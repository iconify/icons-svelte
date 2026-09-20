<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b_psb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b_psb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:celr" {...props}></Icon>
