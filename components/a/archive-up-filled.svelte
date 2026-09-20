<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e71r7tbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e71r7tbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-up-filled" {...props}></Icon>
