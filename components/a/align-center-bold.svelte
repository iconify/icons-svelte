<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxgrrx8od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxgrrx8od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:align-center-bold" {...props}></Icon>
