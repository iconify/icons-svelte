<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3xzofb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3xzofb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-left" {...props}></Icon>
