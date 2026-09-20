<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2_qjfm6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_qjfm6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-box-fill" {...props}></Icon>
