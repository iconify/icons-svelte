<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_m5tq8yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_m5tq8yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cow-solid" {...props}></Icon>
