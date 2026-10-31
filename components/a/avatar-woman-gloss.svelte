<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y07gvub7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y07gvub7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-woman-gloss" {...props}></Icon>
