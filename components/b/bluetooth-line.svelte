<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf6lz4lbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf6lz4lbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bluetooth-line" {...props}></Icon>
