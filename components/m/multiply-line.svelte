<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmu4csbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmu4csbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:multiply-line" {...props}></Icon>
