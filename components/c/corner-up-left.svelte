<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlq7aeugm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlq7aeugm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:corner-up-left" {...props}></Icon>
