<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhleupbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhleupbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-fork-sharp" {...props}></Icon>
