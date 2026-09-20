<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iac8q5bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iac8q5bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-circle-line" {...props}></Icon>
