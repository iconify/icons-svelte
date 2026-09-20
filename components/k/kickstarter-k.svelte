<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw31-9b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qw31-9b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:kickstarter-k" {...props}></Icon>
