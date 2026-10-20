<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz8tqk1vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz8tqk1vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heart-pulse" {...props}></Icon>
