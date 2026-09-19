<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lie-7lbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lie-7lbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-justify-end" {...props}></Icon>
