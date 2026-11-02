<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzc1np7iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzc1np7iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:figure-fill" {...props}></Icon>
