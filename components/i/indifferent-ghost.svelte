<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw641_f4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw641_f4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:indifferent-ghost" {...props}></Icon>
