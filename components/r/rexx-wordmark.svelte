<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9rcu-b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i9rcu-b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rexx-wordmark" {...props}></Icon>
