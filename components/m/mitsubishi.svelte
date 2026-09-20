<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z277job2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z277job2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mitsubishi" {...props}></Icon>
