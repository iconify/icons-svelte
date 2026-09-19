<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icwdcg1df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1664};
const content = `<path class="icwdcg1df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:camera" {...props}></Icon>
