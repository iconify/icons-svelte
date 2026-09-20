<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grbb75b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grbb75b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flip-smiling-face-filled" {...props}></Icon>
