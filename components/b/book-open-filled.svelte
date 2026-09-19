<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx61fjb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx61fjb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-open-filled" {...props}></Icon>
