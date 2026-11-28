<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmzovnboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmzovnboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-diff-solid" {...props}></Icon>
