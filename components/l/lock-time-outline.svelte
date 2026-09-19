<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq_7pjv9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq_7pjv9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:lock-time-outline" {...props}></Icon>
