<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t26_t2uqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t26_t2uqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lamp-bold" {...props}></Icon>
