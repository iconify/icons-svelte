<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gko5mnbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gko5mnbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:paragraph-center-align-bold" {...props}></Icon>
