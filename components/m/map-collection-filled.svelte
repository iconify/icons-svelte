<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j25hdxidg.css';
import '../../css/e/esl7uqcwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j25hdxidg"/><path class="esl7uqcwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-collection-filled" {...props}></Icon>
