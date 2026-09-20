<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt53-_mit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt53-_mit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:atlassian-logo" {...props}></Icon>
