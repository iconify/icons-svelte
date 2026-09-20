<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls27mabel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls27mabel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-symbols" {...props}></Icon>
