<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isdg-2boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isdg-2boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gender-female" {...props}></Icon>
