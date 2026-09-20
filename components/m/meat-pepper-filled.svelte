<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjn2x4nmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjn2x4nmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:meat-pepper-filled" {...props}></Icon>
