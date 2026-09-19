<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayizykitk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayizykitk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-right-line-filled" {...props}></Icon>
