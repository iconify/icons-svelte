<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfnqrjbwb.css';
import '../../css/f/ft8o1xber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfnqrjbwb"/><path class="ft8o1xber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palace-1-filled" {...props}></Icon>
