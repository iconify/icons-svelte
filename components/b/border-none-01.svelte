<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn0rtdylg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0rtdylg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-none-01" {...props}></Icon>
