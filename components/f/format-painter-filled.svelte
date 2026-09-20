<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of6l21bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of6l21bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:format-painter-filled" {...props}></Icon>
