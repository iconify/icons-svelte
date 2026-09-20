<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eog_x572l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eog_x572l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:noodle-filled" {...props}></Icon>
