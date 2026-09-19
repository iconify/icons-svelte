<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4k-5itrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4k-5itrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-center-filled" {...props}></Icon>
