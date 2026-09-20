<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-dzn9u3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-dzn9u3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlemarketingplatform" {...props}></Icon>
