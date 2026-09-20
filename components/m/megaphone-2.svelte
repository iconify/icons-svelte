<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrjocabky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrjocabky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:megaphone-2" {...props}></Icon>
