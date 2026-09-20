<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4iozj.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4iozj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:circle-twotone" {...props}></Icon>
