<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9x8dib2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x8dib2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:face-neutral" {...props}></Icon>
