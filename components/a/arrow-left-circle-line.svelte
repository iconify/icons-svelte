<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5-_om8vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5-_om8vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-circle-line" {...props}></Icon>
