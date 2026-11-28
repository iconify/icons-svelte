<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyzyoz2dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyzyoz2dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-look-left-solid" {...props}></Icon>
