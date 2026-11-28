<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg4uubq-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4uubq-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:panda-solid" {...props}></Icon>
