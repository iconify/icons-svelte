<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s58z6bw5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary s58z6bw5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-duotone" {...props}></Icon>
