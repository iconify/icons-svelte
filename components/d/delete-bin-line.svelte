<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g854m9ish.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g854m9ish"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-line" {...props}></Icon>
