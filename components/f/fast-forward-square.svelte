<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anjs0bcpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="anjs0bcpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fast-forward-square" {...props}></Icon>
