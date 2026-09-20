<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-f8hredq.css';
import '../../css/c/c0k_mybxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-f8hredq"/><path class="c0k_mybxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-book-open-filled" {...props}></Icon>
