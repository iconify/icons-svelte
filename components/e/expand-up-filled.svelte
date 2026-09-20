<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjrm-7bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrm-7bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:expand-up-filled" {...props}></Icon>
