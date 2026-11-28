<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmihy0bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmihy0bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-code-solid" {...props}></Icon>
