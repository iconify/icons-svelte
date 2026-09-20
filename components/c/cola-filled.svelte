<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufphf7byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufphf7byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cola-filled" {...props}></Icon>
