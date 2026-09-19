<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-y4uq50q.css';
import '../../css/v/v4bg1ccwj.css';
import '../../css/z/zlnvfbcfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-y4uq50q"/><path class="v4bg1ccwj"/><path class="zlnvfbcfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rfid" {...props}></Icon>
