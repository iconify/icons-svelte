<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enzq9n-th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enzq9n-th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cross-2-fill" {...props}></Icon>
