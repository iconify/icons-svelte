<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c14jiy.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-38.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c14jiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:play-twotone" {...props}></Icon>
