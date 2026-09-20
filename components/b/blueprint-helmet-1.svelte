<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwyl8uboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwyl8uboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blueprint-helmet-1" {...props}></Icon>
