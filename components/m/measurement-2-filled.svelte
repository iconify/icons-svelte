<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7h7p0mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7h7p0mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:measurement-2-filled" {...props}></Icon>
