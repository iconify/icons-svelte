<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd7r44bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd7r44bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:projects-line" {...props}></Icon>
