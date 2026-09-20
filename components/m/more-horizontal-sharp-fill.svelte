<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs74ptb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs74ptb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:more-horizontal-sharp-fill" {...props}></Icon>
