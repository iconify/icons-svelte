<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttenm5bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttenm5bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-open" {...props}></Icon>
