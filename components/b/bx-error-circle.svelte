<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlfq5tuk.css';
import '../../css/l/leqoybczl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlfq5tuk"/><path class="leqoybczl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-error-circle" {...props}></Icon>
