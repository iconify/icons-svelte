<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb7-6ib7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb7-6ib7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:equal-fill" {...props}></Icon>
