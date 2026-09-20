<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8vzjhb9f.css';
import '../../css/j/jmm-qubuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8vzjhb9f"/><path class="jmm-qubuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-marked-filled" {...props}></Icon>
