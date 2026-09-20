<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqne-81aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqne-81aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-input-filled" {...props}></Icon>
