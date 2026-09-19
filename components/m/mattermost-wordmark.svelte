<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-g93_t9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f-g93_t9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mattermost-wordmark" {...props}></Icon>
