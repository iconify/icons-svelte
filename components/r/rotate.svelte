<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqxwg5bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqxwg5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rotate" {...props}></Icon>
