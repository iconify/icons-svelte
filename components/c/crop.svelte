<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ijo9bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ijo9bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:crop" {...props}></Icon>
