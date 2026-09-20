<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7ycbjbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ycbjbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wechat-workdocs-filled" {...props}></Icon>
