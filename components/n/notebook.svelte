<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzm3jzvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzm3jzvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:notebook" {...props}></Icon>
