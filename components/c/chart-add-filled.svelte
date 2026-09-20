<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9penwvtt.css';
import '../../css/f/f-2vaaboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9penwvtt"/><path class="f-2vaaboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-add-filled" {...props}></Icon>
