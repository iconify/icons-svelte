<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oez6-234v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oez6-234v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-up-filled" {...props}></Icon>
