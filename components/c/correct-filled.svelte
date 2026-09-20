<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b98-y_bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b98-y_bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:correct-filled" {...props}></Icon>
