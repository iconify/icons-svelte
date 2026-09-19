<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcciu0o0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcciu0o0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:backspace" {...props}></Icon>
