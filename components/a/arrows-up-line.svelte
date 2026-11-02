<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5b26_6ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5b26_6ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-up-line" {...props}></Icon>
