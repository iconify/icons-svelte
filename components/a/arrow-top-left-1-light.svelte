<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-ytb230b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ytb230b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-1-light" {...props}></Icon>
