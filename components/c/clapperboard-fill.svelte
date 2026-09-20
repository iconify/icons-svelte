<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntkkgxbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntkkgxbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clapperboard-fill" {...props}></Icon>
