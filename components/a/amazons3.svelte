<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbfftllxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbfftllxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazons3" {...props}></Icon>
