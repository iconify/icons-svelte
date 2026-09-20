<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzkaz2bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzkaz2bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:high-level" {...props}></Icon>
