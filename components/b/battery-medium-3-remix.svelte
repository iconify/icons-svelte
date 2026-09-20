<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8vq4jb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8vq4jb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:battery-medium-3-remix" {...props}></Icon>
