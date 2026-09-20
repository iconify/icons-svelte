<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3knuo1-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3knuo1-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell-check" {...props}></Icon>
