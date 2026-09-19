<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aop2s9bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":746};
const content = `<path class="aop2s9bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bus" {...props}></Icon>
