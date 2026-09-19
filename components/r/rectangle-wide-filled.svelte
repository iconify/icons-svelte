<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2in0hboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="j2in0hboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rectangle-wide-filled" {...props}></Icon>
