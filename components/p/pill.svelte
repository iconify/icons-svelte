<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ittf-hbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ittf-hbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pill" {...props}></Icon>
