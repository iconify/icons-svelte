<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii2hbuh9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2hbuh9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-a-z-filled" {...props}></Icon>
