<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_-m2b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we_-m2b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:download-done" {...props}></Icon>
