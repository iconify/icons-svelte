<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy42re5xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy42re5xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:git-branch" {...props}></Icon>
