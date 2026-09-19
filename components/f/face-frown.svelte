<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk19sqbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk19sqbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:face-frown" {...props}></Icon>
