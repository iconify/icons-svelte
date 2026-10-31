<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi92mggmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi92mggmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-fill-round" {...props}></Icon>
