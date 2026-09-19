<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go-r78b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go-r78b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-filled" {...props}></Icon>
