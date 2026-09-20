<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzd8yibya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzd8yibya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-10-line" {...props}></Icon>
