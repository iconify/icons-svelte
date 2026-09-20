<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t21_8ba5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t21_8ba5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dashboard-line" {...props}></Icon>
