<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5i70lbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5i70lbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:adguard-logo-bold" {...props}></Icon>
