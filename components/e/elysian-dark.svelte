<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igt5iubxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igt5iubxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elysian-dark" {...props}></Icon>
