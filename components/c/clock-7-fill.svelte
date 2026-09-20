<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je37nc8jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je37nc8jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-7-fill" {...props}></Icon>
