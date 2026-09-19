<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjvmhcc6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvmhcc6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-3-square-light" {...props}></Icon>
