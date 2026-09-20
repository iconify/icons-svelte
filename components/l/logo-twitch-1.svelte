<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20g7xb6e.css';
import '../../css/o/o557kdpvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h20g7xb6e"/><path class="o557kdpvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-twitch-1" {...props}></Icon>
