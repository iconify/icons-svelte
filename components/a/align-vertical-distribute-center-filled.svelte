<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8j5qb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8j5qb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-vertical-distribute-center-filled" {...props}></Icon>
