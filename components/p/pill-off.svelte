<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epnoz8anu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epnoz8anu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:pill-off" {...props}></Icon>
