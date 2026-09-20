<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcmvgqgbw.css';
import '../../css/s/sc6d7r8ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcmvgqgbw"/><path class="sc6d7r8ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bookmark-minus-filled" {...props}></Icon>
