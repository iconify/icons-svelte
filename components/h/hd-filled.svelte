<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8bo3ne0r.css';
import '../../css/a/a_gu8acsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8bo3ne0r"/><path class="a_gu8acsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hd-filled" {...props}></Icon>
