<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0s3r5bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j0s3r5bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:home" {...props}></Icon>
