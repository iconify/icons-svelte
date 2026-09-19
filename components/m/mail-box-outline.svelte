<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m25gnw5fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m25gnw5fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:mail-box-outline" {...props}></Icon>
